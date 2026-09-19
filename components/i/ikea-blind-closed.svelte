<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0hg82hni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0hg82hni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-blind-closed" {...props}></Icon>
