<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsy0wdq4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xsy0wdq4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:grid-alt" {...props}></Icon>
