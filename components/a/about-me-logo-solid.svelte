<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwv58h7bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zwv58h7bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:about-me-logo-solid" {...props}></Icon>
