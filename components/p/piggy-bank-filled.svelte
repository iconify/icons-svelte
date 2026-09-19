<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rehko012o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rehko012o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:piggy-bank-filled" {...props}></Icon>
