<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3d_0gbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3d_0gbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jira-software" {...props}></Icon>
