<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulw3ugbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ulw3ugbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:friends-feed-logo-block" {...props}></Icon>
