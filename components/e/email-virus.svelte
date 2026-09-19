<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1qn_nb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z1qn_nb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-virus" {...props}></Icon>
