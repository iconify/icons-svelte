<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drwktt30k.css';
import '../../css/x/xcjpxq55x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drwktt30k"/><path class="xcjpxq55x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-optimization-ai-fleet-routing-api" {...props}></Icon>
