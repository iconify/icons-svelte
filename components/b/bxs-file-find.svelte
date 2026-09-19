<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1si9h-km.css';
import '../../css/b/buc-_ybgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1si9h-km"/><circle class="buc-_ybgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-find" {...props}></Icon>
