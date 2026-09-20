<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlizp9lzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hlizp9lzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-office-presentation-dark" {...props}></Icon>
