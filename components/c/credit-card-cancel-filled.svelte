<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmmzv14io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmmzv14io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-cancel-filled" {...props}></Icon>
