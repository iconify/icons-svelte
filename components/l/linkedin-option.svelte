<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agb97kb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agb97kb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:linkedin-option" {...props}></Icon>
