<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0m83wyra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k0m83wyra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-user-sharp-fill" {...props}></Icon>
