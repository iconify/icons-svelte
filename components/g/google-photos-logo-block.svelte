<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqjqprl0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sqjqprl0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-photos-logo-block" {...props}></Icon>
