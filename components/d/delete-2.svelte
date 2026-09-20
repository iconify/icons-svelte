<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf9770bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf9770bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:delete-2" {...props}></Icon>
