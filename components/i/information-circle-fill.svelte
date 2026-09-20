<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if9an1bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if9an1bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:information-circle-fill" {...props}></Icon>
