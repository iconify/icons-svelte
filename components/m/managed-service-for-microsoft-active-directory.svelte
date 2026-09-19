<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v681d4kxi.css';
import '../../css/m/m9546-bru.css';
import '../../css/q/qr5uq8k0o.css';
import '../../css/m/m1lw9kb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v681d4kxi"/><path class="m9546-bru"/><path class="qr5uq8k0o"/><path class="m1lw9kb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:managed-service-for-microsoft-active-directory" {...props}></Icon>
