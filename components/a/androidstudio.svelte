<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et8aabb_z.css';
import '../../css/a/akwv6qb5q.css';
import '../../css/v/v539uowyg.css';
import '../../css/o/oqolilywl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="et8aabb_z"/><path class="akwv6qb5q"/><path class="v539uowyg"/><circle class="oqolilywl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:androidstudio" {...props}></Icon>
