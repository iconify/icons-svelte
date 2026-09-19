<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gql66jcug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gql66jcug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:home" {...props}></Icon>
