<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm9i-e9gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cm9i-e9gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-check-bold" {...props}></Icon>
