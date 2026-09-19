<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck-1flr4c.css';
import '../../css/b/buc-_ybgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck-1flr4c"/><circle class="buc-_ybgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-find" {...props}></Icon>
