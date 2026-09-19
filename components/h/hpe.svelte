<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4bmm9bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":24};
const content = `<path clip-rule="evenodd" class="a4bmm9bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:hpe" {...props}></Icon>
