<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5oqb4b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-7};
const content = `<path class="o5oqb4b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:rainbow" {...props}></Icon>
