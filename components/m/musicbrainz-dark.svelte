<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2wdzqbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f2wdzqbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:musicbrainz-dark" {...props}></Icon>
