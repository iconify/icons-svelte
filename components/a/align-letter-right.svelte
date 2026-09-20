<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on8hrqu5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on8hrqu5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:align-letter-right" {...props}></Icon>
