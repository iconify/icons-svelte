<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hao_pmbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hao_pmbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:osmand" {...props}></Icon>
