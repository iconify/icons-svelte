<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh9m9zbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh9m9zbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:matomo" {...props}></Icon>
