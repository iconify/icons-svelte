<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8mz3qsho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i8mz3qsho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:pets-allowed-flat" {...props}></Icon>
