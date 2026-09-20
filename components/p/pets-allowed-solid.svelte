<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv7vak98b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hv7vak98b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pets-allowed-solid" {...props}></Icon>
