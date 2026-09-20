<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o08-cac6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o08-cac6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:planet-3-outline" {...props}></Icon>
