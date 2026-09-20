<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibxubqbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibxubqbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hatena-bookmark" {...props}></Icon>
