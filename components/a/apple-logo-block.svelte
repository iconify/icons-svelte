<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smfu5rbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="smfu5rbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:apple-logo-block" {...props}></Icon>
