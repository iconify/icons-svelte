<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo-a9j76f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uo-a9j76f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:dart-logo-block" {...props}></Icon>
