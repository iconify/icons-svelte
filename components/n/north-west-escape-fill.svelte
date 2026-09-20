<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r67n7p6du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r67n7p6du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-west-escape-fill" {...props}></Icon>
