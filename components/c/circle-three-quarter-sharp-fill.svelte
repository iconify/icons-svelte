<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdvcix4ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sdvcix4ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-three-quarter-sharp-fill" {...props}></Icon>
