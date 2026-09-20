<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deb0atb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="deb0atb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:info-sharp-fill" {...props}></Icon>
