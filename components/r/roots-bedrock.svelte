<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktkntsc1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktkntsc1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:roots-bedrock" {...props}></Icon>
