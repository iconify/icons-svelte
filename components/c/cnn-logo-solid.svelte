<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4orqtqmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4orqtqmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:cnn-logo-solid" {...props}></Icon>
