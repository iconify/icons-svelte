<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml95i05tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml95i05tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:archive" {...props}></Icon>
