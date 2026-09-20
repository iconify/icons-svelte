<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtc3gqdsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtc3gqdsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:roll20" {...props}></Icon>
