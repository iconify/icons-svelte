<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kghif2ogu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kghif2ogu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:historic-shield-alt" {...props}></Icon>
