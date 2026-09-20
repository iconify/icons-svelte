<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8t8n6b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="b8t8n6b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:feather-f" {...props}></Icon>
