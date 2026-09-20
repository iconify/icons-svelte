<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sztxhqb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="sztxhqb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:hammer-f" {...props}></Icon>
