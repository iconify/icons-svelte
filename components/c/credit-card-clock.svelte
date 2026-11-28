<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c77mr0lli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c77mr0lli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:credit-card-clock" {...props}></Icon>
