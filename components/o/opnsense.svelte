<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia9cfubzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia9cfubzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:opnsense" {...props}></Icon>
