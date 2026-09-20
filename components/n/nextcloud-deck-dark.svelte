<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7rttpb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7rttpb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-deck-dark" {...props}></Icon>
