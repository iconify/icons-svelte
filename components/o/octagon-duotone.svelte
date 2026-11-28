<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-_z_3qcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-_z_3qcg primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:octagon-duotone" {...props}></Icon>
