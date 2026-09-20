<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1nhcybrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1nhcybrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-account-mail-outline" {...props}></Icon>
