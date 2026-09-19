<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejkle9bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ejkle9bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:phone-vertical" {...props}></Icon>
