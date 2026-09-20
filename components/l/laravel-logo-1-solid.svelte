<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp6ua2ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bp6ua2ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:laravel-logo-1-solid" {...props}></Icon>
