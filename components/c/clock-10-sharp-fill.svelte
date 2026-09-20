<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9w90ebru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y9w90ebru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-10-sharp-fill" {...props}></Icon>
