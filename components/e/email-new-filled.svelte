<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuw8qb5ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vuw8qb5ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-new-filled" {...props}></Icon>
