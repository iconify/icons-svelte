<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1mi_7_by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1mi_7_by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:polkadot" {...props}></Icon>
