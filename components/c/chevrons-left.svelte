<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oanf-ubnv.css';
import '../../css/v/v8ju57b0q.css';
import '../../css/f/fnqikjb0b.css';
import '../../css/d/d7dakccci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oanf-ubnv wm-k"/><path class="v8ju57b0q wm-k"/><path class="fnqikjb0b wm-a"/><path class="d7dakccci wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chevrons-left" {...props}></Icon>
