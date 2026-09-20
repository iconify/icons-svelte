<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on68ukbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="on68ukbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:behance" {...props}></Icon>
