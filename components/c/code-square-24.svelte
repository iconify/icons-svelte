<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmjreii-g.css';
import '../../css/t/tbcp7-bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmjreii-g"/><path class="tbcp7-bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:code-square-24" {...props}></Icon>
