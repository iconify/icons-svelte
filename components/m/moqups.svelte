<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o79_g8b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o79_g8b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:moqups" {...props}></Icon>
