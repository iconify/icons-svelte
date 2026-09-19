<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acx5opb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="acx5opb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:dislike-fill" {...props}></Icon>
