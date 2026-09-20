<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au-d75czj.css';
import '../../css/s/ssbjp9b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="au-d75czj"/><circle class="ssbjp9b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:img-box-duotone" {...props}></Icon>
