<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik0kw2ciw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ik0kw2ciw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:face-grin-solid" {...props}></Icon>
