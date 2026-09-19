<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aellxybok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aellxybok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:logout" {...props}></Icon>
