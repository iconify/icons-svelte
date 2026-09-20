<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z06ct1bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z06ct1bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pets-allowed-remix" {...props}></Icon>
