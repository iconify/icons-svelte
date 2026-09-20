<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdnr9q_oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdnr9q_oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:diaspora" {...props}></Icon>
