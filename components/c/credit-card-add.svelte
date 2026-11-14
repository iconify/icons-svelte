<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3-i9tb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3-i9tb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:credit-card-add" {...props}></Icon>
