<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwj4rxbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwj4rxbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:ati-logo" {...props}></Icon>
