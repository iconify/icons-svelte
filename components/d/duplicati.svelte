<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9rjmmfqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9rjmmfqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:duplicati" {...props}></Icon>
