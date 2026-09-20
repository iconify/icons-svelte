<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqd2dohwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqd2dohwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dataverse" {...props}></Icon>
