<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud-3rhbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud-3rhbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:credit-card-search" {...props}></Icon>
