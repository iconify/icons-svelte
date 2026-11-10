<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7gocf1de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7gocf1de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:mu-capital" {...props}></Icon>
