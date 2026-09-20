<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8syhz-ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8syhz-ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pelican" {...props}></Icon>
