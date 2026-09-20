<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/impvs4byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="impvs4byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:cinema-4d-logo-block" {...props}></Icon>
