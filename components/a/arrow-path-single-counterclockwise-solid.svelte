<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3hdh9k9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3hdh9k9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-single-counterclockwise-solid" {...props}></Icon>
