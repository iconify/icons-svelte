<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jogh7qb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jogh7qb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apacheflink" {...props}></Icon>
