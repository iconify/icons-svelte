<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phfw6ywkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="phfw6ywkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:radial" {...props}></Icon>
