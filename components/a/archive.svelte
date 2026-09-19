<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au98x5bva.css';
import '../../css/t/toacpk17o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au98x5bva"/><path class="toacpk17o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:archive" {...props}></Icon>
