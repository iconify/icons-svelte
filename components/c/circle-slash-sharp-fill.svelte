<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8zsfrlau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8zsfrlau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-slash-sharp-fill" {...props}></Icon>
