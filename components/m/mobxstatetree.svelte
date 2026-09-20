<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_soae0bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_soae0bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mobxstatetree" {...props}></Icon>
