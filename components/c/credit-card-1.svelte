<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-024ibil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-024ibil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:credit-card-1" {...props}></Icon>
