<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4lpm3r4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4lpm3r4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:catalog-option" {...props}></Icon>
