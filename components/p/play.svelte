<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-crd-fry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-crd-fry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:play" {...props}></Icon>
