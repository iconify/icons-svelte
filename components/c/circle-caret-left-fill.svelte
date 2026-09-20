<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd965_b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd965_b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-caret-left-fill" {...props}></Icon>
