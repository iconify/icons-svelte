<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvc9hzisg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvc9hzisg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:les-libraires" {...props}></Icon>
