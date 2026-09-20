<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooetkb5ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3.5,"top":-1};
const content = `<path class="ooetkb5ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:leaf" {...props}></Icon>
