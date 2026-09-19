<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scnqbpb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scnqbpb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:closed-caption" {...props}></Icon>
