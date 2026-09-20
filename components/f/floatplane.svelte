<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb_4tt4ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb_4tt4ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:floatplane" {...props}></Icon>
