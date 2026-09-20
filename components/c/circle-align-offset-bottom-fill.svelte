<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl9d6f0ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl9d6f0ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-align-offset-bottom-fill" {...props}></Icon>
