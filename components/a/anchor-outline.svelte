<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac2-8hbbw.css';
import '../../css/l/lmsrdu7eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="ac2-8hbbw"/><path class="lmsrdu7eq"/><circle class="ac2-8hbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:anchor-outline" {...props}></Icon>
