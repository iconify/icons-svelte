<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx5u0jbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx5u0jbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:git-pull-request" {...props}></Icon>
