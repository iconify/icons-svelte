<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gna6b-1ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gna6b-1ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:carbon-dioxide" {...props}></Icon>
