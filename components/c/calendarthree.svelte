<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivs3jibks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="ivs3jibks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:calendarthree" {...props}></Icon>
