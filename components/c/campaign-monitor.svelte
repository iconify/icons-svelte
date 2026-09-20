<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlj_3z6ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlj_3z6ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:campaign-monitor" {...props}></Icon>
