<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdhqldb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdhqldb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-branch-minus-sharp" {...props}></Icon>
