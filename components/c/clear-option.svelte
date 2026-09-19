<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyk4ir-7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyk4ir-7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:clear-option" {...props}></Icon>
