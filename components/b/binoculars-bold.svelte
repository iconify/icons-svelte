<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muwknjt7p.css';
import '../../css/b/b5jplqbkn.css';
import '../../css/b/bnrsc3bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muwknjt7p"/><path class="b5jplqbkn"/><path clip-rule="evenodd" class="bnrsc3bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:binoculars-bold" {...props}></Icon>
