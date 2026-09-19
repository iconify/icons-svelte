<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2z5i8bzr.css';
import '../../css/q/q-24mgbnq.css';
import '../../css/x/xwymr9bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2z5i8bzr"/><path class="q-24mgbnq"/><path class="xwymr9bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:database-migration-service" {...props}></Icon>
