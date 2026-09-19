<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/borqoqbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="borqoqbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:car" {...props}></Icon>
