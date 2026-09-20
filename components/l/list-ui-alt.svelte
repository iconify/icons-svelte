<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqosw2b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqosw2b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:list-ui-alt" {...props}></Icon>
