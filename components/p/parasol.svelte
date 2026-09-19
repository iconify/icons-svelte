<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5bgb_b8s.css';
import '../../css/c/csm28-9_z.css';
import '../../css/b/bdkeo7bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5bgb_b8s"/><path class="csm28-9_z"/><path class="bdkeo7bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:parasol" {...props}></Icon>
