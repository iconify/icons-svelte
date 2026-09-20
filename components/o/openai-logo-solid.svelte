<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1opg8io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iw1opg8io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:openai-logo-solid" {...props}></Icon>
