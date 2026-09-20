<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r74_oja1e.css';
import '../../css/d/d267sib8p.css';
import '../../css/w/w13gqbpqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r74_oja1e"/><path class="d267sib8p"/><path class="w13gqbpqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:instagram" {...props}></Icon>
