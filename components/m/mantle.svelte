<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skrh6_4wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skrh6_4wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mantle" {...props}></Icon>
