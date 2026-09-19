<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j49hvua4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j49hvua4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:flask-solid" {...props}></Icon>
