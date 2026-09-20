<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya9pjdagh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya9pjdagh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cloud-fog-solid" {...props}></Icon>
